<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q04j8-bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q04j8-bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-settings-spark-remix" {...props}></Icon>
