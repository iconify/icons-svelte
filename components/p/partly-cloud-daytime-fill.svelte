<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuo2kw2qw.css';
import '../../css/n/n54i3ab4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iuo2kw2qw"/><path class="n54i3ab4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:partly-cloud-daytime-fill" {...props}></Icon>
