<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd2-fnpdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jd2-fnpdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:credit-card-disable-remix" {...props}></Icon>
