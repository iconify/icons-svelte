<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3b6p42rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3b6p42rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-record-sharp-fill" {...props}></Icon>
