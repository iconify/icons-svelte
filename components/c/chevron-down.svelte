<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am9rw71zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="am9rw71zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevron-down" {...props}></Icon>
