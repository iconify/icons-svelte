<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5_s15unc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h5_s15unc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mina" {...props}></Icon>
