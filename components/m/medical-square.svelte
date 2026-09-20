<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkuh8za8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkuh8za8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:medical-square" {...props}></Icon>
