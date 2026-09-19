<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cirm-9b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cirm-9b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:question-triangle-24px" {...props}></Icon>
