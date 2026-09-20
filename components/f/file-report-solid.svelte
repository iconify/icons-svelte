<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os1my55bi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="os1my55bi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:file-report-solid" {...props}></Icon>
