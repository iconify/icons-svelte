<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ino_babvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ino_babvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mlk" {...props}></Icon>
