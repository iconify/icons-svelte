<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6d0pw-fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6d0pw-fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:divide" {...props}></Icon>
