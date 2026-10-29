<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhgspvbqn.css';
import '../../css/e/eu5ykpb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhgspvbqn"/><path class="eu5ykpb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevron-left" {...props}></Icon>
