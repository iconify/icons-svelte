<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqk0_3bfl.css';
import '../../css/l/lgb7uffyh.css';
import '../../css/s/syaz7gedi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqk0_3bfl"/><path class="lgb7uffyh"/><path class="syaz7gedi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-stamp-document-bold" {...props}></Icon>
