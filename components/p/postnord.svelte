<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvnjenj-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvnjenj-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:postnord" {...props}></Icon>
