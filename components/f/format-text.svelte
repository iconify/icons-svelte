<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eux2u3jdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eux2u3jdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:format-text" {...props}></Icon>
