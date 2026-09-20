<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/errca7bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="errca7bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-bottom-open-solid" {...props}></Icon>
