<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo3o-8b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo3o-8b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:lolcode" {...props}></Icon>
