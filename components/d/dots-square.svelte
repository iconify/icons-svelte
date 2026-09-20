<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0rko8y9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0rko8y9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-square" {...props}></Icon>
