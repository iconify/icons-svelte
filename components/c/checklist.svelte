<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-s6nhbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-s6nhbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:checklist" {...props}></Icon>
