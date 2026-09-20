<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjv0t2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pjv0t2bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:mic-detailed-fill" {...props}></Icon>
