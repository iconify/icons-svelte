<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1h9t2bpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1h9t2bpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:database-fill" {...props}></Icon>
