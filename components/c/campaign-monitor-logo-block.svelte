<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol6h9rdbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol6h9rdbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:campaign-monitor-logo-block" {...props}></Icon>
