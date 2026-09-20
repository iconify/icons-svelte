<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duyij83lt.css';
import '../../css/s/snztlmsub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duyij83lt"/><path class="snztlmsub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dsrun" {...props}></Icon>
