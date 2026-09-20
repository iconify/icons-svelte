<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojyl--bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojyl--bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:equal-duotone" {...props}></Icon>
