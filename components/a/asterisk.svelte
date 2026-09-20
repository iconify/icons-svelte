<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwo6y5lbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwo6y5lbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:asterisk" {...props}></Icon>
