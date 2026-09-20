<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv1bq6mjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qv1bq6mjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hourglass-remix" {...props}></Icon>
