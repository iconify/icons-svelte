<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6i6wnaac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6i6wnaac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:iheartradio" {...props}></Icon>
