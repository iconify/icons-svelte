<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za8njebkw.css';
import '../../css/z/zstbz94ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="za8njebkw"/><circle class="zstbz94ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:record-fill-12" {...props}></Icon>
