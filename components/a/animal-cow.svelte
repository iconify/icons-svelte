<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6gvpfllf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o6gvpfllf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-cow" {...props}></Icon>
