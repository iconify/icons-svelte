<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6yze_b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6yze_b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:copyright3-filled" {...props}></Icon>
