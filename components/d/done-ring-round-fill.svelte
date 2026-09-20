<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb8drvbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gb8drvbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:done-ring-round-fill" {...props}></Icon>
