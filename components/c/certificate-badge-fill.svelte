<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqm7u3bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wqm7u3bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:certificate-badge-fill" {...props}></Icon>
