<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_i-7bb7z.css';
import '../../css/o/o3283cgee.css';
import '../../css/k/kjo9alciz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v_i-7bb7z"/><path class="o3283cgee"/><path class="kjo9alciz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnet-wave-outline" {...props}></Icon>
