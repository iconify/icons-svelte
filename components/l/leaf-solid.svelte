<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-fvwxbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v-fvwxbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:leaf-solid" {...props}></Icon>
