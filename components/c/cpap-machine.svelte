<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3nib0-4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="y3nib0-4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cpap-machine" {...props}></Icon>
