<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljdfx9b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljdfx9b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-document-light" {...props}></Icon>
