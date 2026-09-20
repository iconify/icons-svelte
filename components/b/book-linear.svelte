<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c6-bipb9j.css';
import '../../css/f/f_gnwzb8z.css';
import '../../css/t/t-007b-3c.css';
import '../../css/f/fx38fz2eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6-bipb9j"/><path class="f_gnwzb8z"/><path class="t-007b-3c"/><path class="fx38fz2eg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-linear" {...props}></Icon>
