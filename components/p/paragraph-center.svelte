<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2pg_dqyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="c2pg_dqyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:paragraph-center" {...props}></Icon>
