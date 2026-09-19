<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cybmyib3k.css';
import '../../css/r/rdoevbfyc.css';
import '../../css/i/im1u3sbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cybmyib3k"/><path class="rdoevbfyc"/><path class="im1u3sbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:anthos-config-management" {...props}></Icon>
