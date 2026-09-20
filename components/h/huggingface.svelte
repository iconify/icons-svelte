<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xula-6ban.css';
import '../../css/v/vtz50zjpg.css';
import '../../css/z/zawp9sbpf.css';
import '../../css/k/k6jq5_i3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xula-6ban"/><path class="vtz50zjpg"/><path class="zawp9sbpf"/><path class="k6jq5_i3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:huggingface" {...props}></Icon>
