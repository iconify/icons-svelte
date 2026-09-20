<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz7-v-bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz7-v-bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-up-light" {...props}></Icon>
