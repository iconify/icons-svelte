<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss7r9ybtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss7r9ybtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:road-sign-hairpin-turn-left-bold" {...props}></Icon>
