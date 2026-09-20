<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5tm-zk0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="s5tm-zk0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:nfccheckpoint" {...props}></Icon>
