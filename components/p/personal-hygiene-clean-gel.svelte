<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozo2onbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozo2onbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-clean-gel" {...props}></Icon>
