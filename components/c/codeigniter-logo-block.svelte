<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlcflx_yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qlcflx_yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codeigniter-logo-block" {...props}></Icon>
