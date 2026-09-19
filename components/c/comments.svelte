<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aao_zi_4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aao_zi_4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:comments" {...props}></Icon>
