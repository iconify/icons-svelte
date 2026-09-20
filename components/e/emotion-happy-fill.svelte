<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjmoh7xin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjmoh7xin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:emotion-happy-fill" {...props}></Icon>
