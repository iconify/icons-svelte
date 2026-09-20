<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut7ftg3vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ut7ftg3vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:circle-arrow-left-down-filled" {...props}></Icon>
