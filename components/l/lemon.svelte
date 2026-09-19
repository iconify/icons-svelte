<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdwunab8w.css';
import '../../css/h/hjv1atbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdwunab8w"/><path class="hjv1atbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:lemon" {...props}></Icon>
