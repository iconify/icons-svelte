<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-hxxlioz.css';
import '../../css/n/nd5zkmbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-hxxlioz"/><path clip-rule="evenodd" class="nd5zkmbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mastodon-24" {...props}></Icon>
