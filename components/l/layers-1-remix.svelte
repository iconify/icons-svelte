<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezdg7vhee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ezdg7vhee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layers-1-remix" {...props}></Icon>
