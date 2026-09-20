<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqz_8_baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqz_8_baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:percent" {...props}></Icon>
