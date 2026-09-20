<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss2xjkb3d.css';
import '../../css/n/n_iamfbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss2xjkb3d"/><path class="n_iamfbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:metav" {...props}></Icon>
