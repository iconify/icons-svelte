<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s71wdfb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s71wdfb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:redmine" {...props}></Icon>
