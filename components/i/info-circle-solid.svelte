<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8w3rabjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8w3rabjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:info-circle-solid" {...props}></Icon>
