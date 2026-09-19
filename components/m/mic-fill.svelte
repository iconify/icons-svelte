<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj-378b7y.css';
import '../../css/n/nblq3cbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj-378b7y"/><path class="nblq3cbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:mic-fill" {...props}></Icon>
