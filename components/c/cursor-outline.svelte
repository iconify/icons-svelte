<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvm_hy68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvm_hy68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:cursor-outline" {...props}></Icon>
