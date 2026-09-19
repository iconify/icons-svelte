<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn9fkv6ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qn9fkv6ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:link-broken-alt-01" {...props}></Icon>
