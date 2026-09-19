<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwg_5dfby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwg_5dfby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:alarabiya-ch" {...props}></Icon>
