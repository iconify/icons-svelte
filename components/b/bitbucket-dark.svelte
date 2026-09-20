<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkpf_55pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kkpf_55pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bitbucket-dark" {...props}></Icon>
