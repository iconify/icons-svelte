<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nri6v8bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nri6v8bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:label-filled" {...props}></Icon>
