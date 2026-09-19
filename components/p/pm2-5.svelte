<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npgbpkpyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npgbpkpyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pm2-5" {...props}></Icon>
