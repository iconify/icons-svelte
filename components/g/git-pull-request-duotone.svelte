<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9on4tfbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary y9on4tfbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-pull-request-duotone" {...props}></Icon>
