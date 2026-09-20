<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6f4tmb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6f4tmb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-box-lock-open-outline" {...props}></Icon>
