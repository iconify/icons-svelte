<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_gjhpb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_gjhpb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mastodon" {...props}></Icon>
