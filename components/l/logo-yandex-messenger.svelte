<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj_tu-bmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vj_tu-bmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-yandex-messenger" {...props}></Icon>
