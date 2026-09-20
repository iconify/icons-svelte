<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l84sn-bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l84sn-bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:on-button-fill" {...props}></Icon>
