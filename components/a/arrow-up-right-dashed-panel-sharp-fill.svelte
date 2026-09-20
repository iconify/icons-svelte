<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec6b-jbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ec6b-jbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-up-right-dashed-panel-sharp-fill" {...props}></Icon>
