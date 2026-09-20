<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqt-btbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqt-btbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pause-presentation-fill" {...props}></Icon>
