<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej3fxxlaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ej3fxxlaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:mobile-outline" {...props}></Icon>
