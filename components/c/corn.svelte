<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obdmvrb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="obdmvrb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:corn" {...props}></Icon>
