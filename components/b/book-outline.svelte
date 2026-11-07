<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0gvw96fa.css';
import '../../css/h/hw9ee6laf.css';
import '../../css/a/aitp4sbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0gvw96fa"/><path class="hw9ee6laf"/><path clip-rule="evenodd" class="aitp4sbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-outline" {...props}></Icon>
