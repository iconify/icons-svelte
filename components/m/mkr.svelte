<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx8m87bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx8m87bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mkr" {...props}></Icon>
