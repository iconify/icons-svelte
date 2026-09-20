<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6ovqkmll.css';
import '../../css/b/bi7kcybaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6ovqkmll"/><path class="bi7kcybaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hail-fill" {...props}></Icon>
