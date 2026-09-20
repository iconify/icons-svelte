<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-8ong1fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n-8ong1fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pulse2" {...props}></Icon>
