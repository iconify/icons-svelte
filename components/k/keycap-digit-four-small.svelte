<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1olqofzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d1olqofzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-four-small" {...props}></Icon>
