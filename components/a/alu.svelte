<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvoy7epho.css';
import '../../css/h/hyinz4b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvoy7epho"/><path class="hyinz4b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:alu" {...props}></Icon>
