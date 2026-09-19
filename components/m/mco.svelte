<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-1qv-lda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o-1qv-lda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mco" {...props}></Icon>
