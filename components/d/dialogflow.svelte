<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwb61c__y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwb61c__y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:dialogflow" {...props}></Icon>
