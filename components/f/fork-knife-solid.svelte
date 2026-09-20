<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfh4iu6hg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qfh4iu6hg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:fork-knife-solid" {...props}></Icon>
