<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq_3n607q.css';
import '../../css/n/nblq3cbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq_3n607q"/><path class="nblq3cbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:mic-outline" {...props}></Icon>
