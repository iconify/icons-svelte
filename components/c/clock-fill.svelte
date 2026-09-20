<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok68s2t7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ok68s2t7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clock-fill" {...props}></Icon>
