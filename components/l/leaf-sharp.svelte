<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjahfzb-f.css';
import '../../css/n/nb1ykgawv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjahfzb-f"/><path class="nb1ykgawv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:leaf-sharp" {...props}></Icon>
