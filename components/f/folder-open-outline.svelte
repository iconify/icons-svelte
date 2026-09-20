<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqlot2byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqlot2byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-open-outline" {...props}></Icon>
