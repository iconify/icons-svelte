<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlmk6mb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlmk6mb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:propc" {...props}></Icon>
