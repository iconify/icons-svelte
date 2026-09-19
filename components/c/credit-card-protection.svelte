<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc8lrbwyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zc8lrbwyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-card-protection" {...props}></Icon>
