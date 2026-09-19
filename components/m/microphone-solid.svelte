<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc10j4kob.css';
import '../../css/t/tw4lkvbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jc10j4kob"/><path class="tw4lkvbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:microphone-solid" {...props}></Icon>
