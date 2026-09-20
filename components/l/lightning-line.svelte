<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnih8dbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hnih8dbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:lightning-line" {...props}></Icon>
