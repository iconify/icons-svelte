<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f93zup36c.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dahxw4bbt.css';
import '../../css/k/k1whppbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f93zup36c secondary"/><g class="dt0cm9dhy primary"><path class="dahxw4bbt"/><path class="k1whppbep"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mastodon-duo" {...props}></Icon>
