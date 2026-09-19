<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuejpjjmz.css';
import '../../css/b/be4ff7bzh.css';
import '../../css/z/zhu4enjix.css';
import '../../css/u/u2bhkjb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vuejpjjmz"/><circle class="be4ff7bzh"/><circle class="zhu4enjix"/><path class="u2bhkjb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:code-working-outline" {...props}></Icon>
