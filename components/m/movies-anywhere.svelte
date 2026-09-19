<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk2da1b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk2da1b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:movies-anywhere" {...props}></Icon>
