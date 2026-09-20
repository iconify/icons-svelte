<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dibn1jbkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dibn1jbkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bolt-off-filled" {...props}></Icon>
