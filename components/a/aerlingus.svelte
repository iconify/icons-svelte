<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-pr9dbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-pr9dbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aerlingus" {...props}></Icon>
