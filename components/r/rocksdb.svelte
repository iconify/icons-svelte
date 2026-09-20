<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np_tewe7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np_tewe7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rocksdb" {...props}></Icon>
