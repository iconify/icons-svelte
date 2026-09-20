<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k73k7yq-m.css';
import '../../css/u/u79pk-b6p.css';
import '../../css/k/k74euduoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k73k7yq-m"/><path class="u79pk-b6p"/><path class="k74euduoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:common-file-text-add-bold" {...props}></Icon>
