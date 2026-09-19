<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9286gj6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9286gj6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-incoming-forward" {...props}></Icon>
