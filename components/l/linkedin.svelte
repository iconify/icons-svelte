<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckulpe9ec.css';
import '../../css/h/h_2ddrein.css';
import '../../css/f/fa_16t6kl.css';
import '../../css/b/bs-dfccax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckulpe9ec"/><path class="h_2ddrein"/><circle class="fa_16t6kl"/><path class="bs-dfccax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:linkedin" {...props}></Icon>
