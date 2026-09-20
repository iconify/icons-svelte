<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqx3m-pme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bqx3m-pme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-arrow-up-filled" {...props}></Icon>
