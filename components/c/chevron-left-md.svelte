<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej6w2kb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej6w2kb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-left-md" {...props}></Icon>
