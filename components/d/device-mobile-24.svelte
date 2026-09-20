<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvve5bzij.css';
import '../../css/u/u9ixn_sru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvve5bzij"/><path class="u9ixn_sru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-mobile-24" {...props}></Icon>
