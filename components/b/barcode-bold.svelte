<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eumvyw40q.css';
import '../../css/o/ola1aj4br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eumvyw40q"/><path class="ola1aj4br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:barcode-bold" {...props}></Icon>
