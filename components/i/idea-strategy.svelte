<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-d7atbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-d7atbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:idea-strategy" {...props}></Icon>
