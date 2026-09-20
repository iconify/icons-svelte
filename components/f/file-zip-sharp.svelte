<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swa786bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swa786bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-zip-sharp" {...props}></Icon>
